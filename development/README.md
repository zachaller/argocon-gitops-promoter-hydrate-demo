# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 26843798d5d2fa2f90ed23d88226ceb5dc4188d6
kustomize build ./user-configuration/development
```
