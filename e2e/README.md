# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 4b87b7bb1bea9748b224d3bf1d6d0abece9aa738
kustomize build ./user-configuration/staging/e2e
```
