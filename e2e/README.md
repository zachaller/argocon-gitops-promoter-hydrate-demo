# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 88057398b972a7ffcbd0ee0e19096d8b0ac6ddd3
kustomize build ./user-configuration/staging/e2e
```
