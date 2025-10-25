# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout c9f161c7fe1915519abedcec4ce8198c14211907
kustomize build ./user-configuration/staging/integration
```
