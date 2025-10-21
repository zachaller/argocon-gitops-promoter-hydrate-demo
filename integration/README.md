# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout cf1ef74f30e52669ce7d1d8220b39c916a3d3ec8
kustomize build ./user-configuration/staging/integration
```
