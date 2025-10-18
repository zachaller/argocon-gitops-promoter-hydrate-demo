# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout c71b8ed9ed64384a51349b4818077c49a5d61d66
kustomize build ./user-configuration/staging/integration
```
