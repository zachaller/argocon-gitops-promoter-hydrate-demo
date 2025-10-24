# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 7f5b0d604eb4d8e19d215283606558cdf194b439
kustomize build ./user-configuration/staging/e2e
```
