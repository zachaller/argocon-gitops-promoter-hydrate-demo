# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 10e4d1bf1cdbf5f0307a5d762e8f27b768f5a6fb
kustomize build ./user-configuration/staging/e2e
```
