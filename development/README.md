# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout c5f91d66b8a39e32337760d33c920efa6e189fe3
kustomize build ./user-configuration/development
```
