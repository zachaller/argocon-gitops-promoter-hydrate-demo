# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 141e7f524e8c1bc0f31e445ffd4f9d1561cc8f51
kustomize build ./user-configuration/staging/integration
```
