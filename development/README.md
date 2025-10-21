# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 2475cb74a3ea305ed918b245a1e31915fee8b41d
kustomize build ./user-configuration/development
```
