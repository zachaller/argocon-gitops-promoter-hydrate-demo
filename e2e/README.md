# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 0743cae8147a2dba1ba4397be1561d1e433f9a0f
kustomize build ./user-configuration/staging/e2e
```
