# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 6b1e6437898c6e8a6f7472e5ac547e4b5208f658
kustomize build ./user-configuration/staging/e2e
```
