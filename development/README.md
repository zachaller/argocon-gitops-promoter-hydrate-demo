# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 1cc8772d6a4bcd665218f4e6c3246d3a4d1a1134
kustomize build ./user-configuration/development
```
