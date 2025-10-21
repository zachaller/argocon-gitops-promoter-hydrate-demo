# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout b71b9abcd8ad139d0223964b5fe82288fe551a50
kustomize build ./user-configuration/staging/integration
```
