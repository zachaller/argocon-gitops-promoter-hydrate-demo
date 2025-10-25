# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout a9ab9ec5a823d31e66e1e4926dbd0b0ff2757758
kustomize build ./user-configuration/development
```
