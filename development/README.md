# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout a6014bd7d9af3d152e671e46170b00bff204d475
kustomize build ./user-configuration/development
```
