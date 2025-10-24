# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 19f67a4389e02f2d3dcecfed191f7d17dbfc0c3d
kustomize build ./user-configuration/staging/e2e
```
