# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 5d02875e44b63c0d10f67f905a5d43e1d3dc1f35
kustomize build ./user-configuration/staging/e2e
```
