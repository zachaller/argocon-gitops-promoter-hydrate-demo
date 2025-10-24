# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 6d5a3d71c6d29671083f15b38cb11763a7e7b802
kustomize build ./user-configuration/development
```
