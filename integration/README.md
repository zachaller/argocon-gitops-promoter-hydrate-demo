# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout ba7a6eaa8d95496febf03cf09eaf471a3e9afd37
kustomize build ./user-configuration/staging/integration
```
