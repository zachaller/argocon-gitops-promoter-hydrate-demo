# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout b9695f93a7d2efb01422e1f7904f8c4ca4c134af
kustomize build ./user-configuration/staging/e2e
```
