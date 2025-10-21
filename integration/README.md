# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout dce5dd88665022f4665df6ab33962e1bdcc40c06
kustomize build ./user-configuration/staging/integration
```
