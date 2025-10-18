# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout d8f68b8e9e8c34c75b8662fcfdc1ed40de05338c
kustomize build ./user-configuration/staging/e2e
```
