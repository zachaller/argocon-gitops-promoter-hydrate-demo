# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 49c58a2d59b6cb76fbfc4abd8131e426b805f755
kustomize build ./user-configuration/development
```
