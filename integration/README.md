# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 1faf9ba6fff90f749b922459221c597fe823dd2d
kustomize build ./user-configuration/staging/integration
```
