# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 15c126ea4636653430dcfb47180db47709e6cd51
kustomize build ./user-configuration/staging/e2e
```
