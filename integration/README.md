# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 8d34a346a51a1790360d319e9738064bb7b69ec6
kustomize build ./user-configuration/staging/integration
```
