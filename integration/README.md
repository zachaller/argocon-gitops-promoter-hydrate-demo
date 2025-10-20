# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 1f3d73c14d831995b78fa37c04c6ce8b01004dc7
kustomize build ./user-configuration/staging/integration
```
