# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout b511d9aed2839667e2cedd51d444b5c81d188365
kustomize build ./user-configuration/development
```
