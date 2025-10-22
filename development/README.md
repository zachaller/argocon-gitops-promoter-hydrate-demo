# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout d50cde2675adbaa8aaa471e19b5d849f550c3b50
kustomize build ./user-configuration/development
```
