# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout a84942f2f50edd7267693f23bd08455e6e959bd1
kustomize build ./user-configuration/staging/integration
```
