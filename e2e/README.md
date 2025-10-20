# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 3dd39ba97b5cd1273d3ad79902d5a66e6fb33f1d
kustomize build ./user-configuration/staging/e2e
```
