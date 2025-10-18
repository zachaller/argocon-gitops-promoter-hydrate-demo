# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout ee5263c59fc45de350d3d2835366120c4e86cfd9
kustomize build ./user-configuration/staging/integration
```
