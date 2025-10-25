# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 291d93ffadde2771c6e51a290c2f7d83f8861d3d
kustomize build ./user-configuration/staging/e2e
```
