# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout db74e4d9fee0268a86ffe288d31d2b81c53da927
kustomize build ./user-configuration/staging/integration
```
