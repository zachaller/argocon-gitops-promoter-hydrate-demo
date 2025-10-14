# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 7fd6183ae5e3b8cc458ff42880d4bc26d83767ef
kustomize build ./user-configuration/development
```
