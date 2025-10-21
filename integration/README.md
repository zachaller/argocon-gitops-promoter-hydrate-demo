# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 1c17ca768a02c4a1e2166ae14e92d2028b98054a
kustomize build ./user-configuration/staging/integration
```
