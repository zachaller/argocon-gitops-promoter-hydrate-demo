# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 116a577415272159ab43d421b501879659264f8d
kustomize build ./user-configuration/production/us-east-2
```
