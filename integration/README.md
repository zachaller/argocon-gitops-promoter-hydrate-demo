# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout d3b663d9b824dcd1c88537d22055865f3d54f7b9
kustomize build ./user-configuration/staging/integration
```
