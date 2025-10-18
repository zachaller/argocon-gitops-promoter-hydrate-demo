# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout bf80dbc21e6ca5fe90064516f7ee33061c1d89fc
kustomize build ./user-configuration/staging/e2e
```
