# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout da186ecbd7f75119f47c152bfd477c797e8406ba
kustomize build ./user-configuration/staging/integration
```
