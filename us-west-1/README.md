# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 8da15b44368dbbeb5674bb9ab378116a22bc1efd
kustomize build ./user-configuration/production/us-west-1
```
