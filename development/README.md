# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 6fd5b678ea5cf29d8c9a807e55766b1ae1c4a986
kustomize build ./user-configuration/development
```
