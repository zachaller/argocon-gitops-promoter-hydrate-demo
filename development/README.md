# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout d1ca0b53b16af7509ba51a8ddeafe88214b4fff6
kustomize build ./user-configuration/development
```
