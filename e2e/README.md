# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 232e624996380da554d41a6627a9b5dba7fe5f18
kustomize build ./user-configuration/staging/e2e
```
