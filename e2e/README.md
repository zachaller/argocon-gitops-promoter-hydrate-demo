# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 0a6ecc02f44e8d60138e17d412a5630b5d6ce57d
kustomize build ./user-configuration/staging/e2e
```
