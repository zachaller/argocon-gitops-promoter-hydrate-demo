# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 1dacfb017f38b00d27bda51b7b97033c90d9cb19
kustomize build ./user-configuration/production/us-west-1
```
