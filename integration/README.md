# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout bfc73fe8e2037f2d1d53a13b18e2a53f4b41c211
kustomize build ./user-configuration/staging/integration
```
