# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout dc69441c1b00ead51de2f6917c1a86cd480c5438
kustomize build ./user-configuration/production/us-east-2
```
