# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 88b166bb2448f2e2208baa5739a51a124075dd16
kustomize build ./user-configuration/staging/e2e
```
