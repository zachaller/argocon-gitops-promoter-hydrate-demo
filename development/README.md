# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout c3445257430319a62c2b9a7181e9dc0af16c9c40
kustomize build ./user-configuration/development
```
