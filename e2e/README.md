# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout dfdeca1c43bd42c1d11c4d0cf04cf4b29ab862ec
kustomize build ./user-configuration/staging/e2e
```
