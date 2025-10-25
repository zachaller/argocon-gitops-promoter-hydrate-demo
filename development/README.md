# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout f832d9c9ed00c0659bfef4b403df1d821c9bf48a
kustomize build ./user-configuration/development
```
