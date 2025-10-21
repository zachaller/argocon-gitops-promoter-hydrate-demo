# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 8fcedfcd174e5fabad21ec9b06e6c53b53b0329d
kustomize build ./user-configuration/development
```
