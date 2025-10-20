# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 699c96f0aba850920200e5778328ee4a5d1e5cd5
kustomize build ./user-configuration/staging/e2e
```
