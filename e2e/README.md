# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 858100dcada99d826f395523f8ba7300df5feffc
kustomize build ./user-configuration/staging/e2e
```
