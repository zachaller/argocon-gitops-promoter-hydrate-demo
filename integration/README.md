# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 69fe6e7875b45a0c86324a99807c32cab7cb8509
kustomize build ./user-configuration/staging/integration
```
