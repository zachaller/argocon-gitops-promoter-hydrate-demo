# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 7b2d8adf96f6fc75ed5e83f53768f935484fe8d6
kustomize build ./user-configuration/development
```
