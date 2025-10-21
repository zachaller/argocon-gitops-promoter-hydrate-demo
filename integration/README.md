# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 4b1105d3a9351e00458027d8b94f9351b97293de
kustomize build ./user-configuration/staging/integration
```
