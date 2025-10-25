# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout a4f55a7d05d0b3d5fbf8bf4bd219f41d367b44d6
kustomize build ./user-configuration/staging/e2e
```
