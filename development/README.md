# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 5fcd61230671a69d91294b4d1375f14e1d4ab9f3
kustomize build ./user-configuration/development
```
