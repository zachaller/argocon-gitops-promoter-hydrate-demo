# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout f4a291bcae55ee813db72e50e51396ddf7b1e1b0
kustomize build ./user-configuration/staging/e2e
```
