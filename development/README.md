# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 5c92fc88c9a1a9ae3b6549835fefc00f182d173d
kustomize build ./user-configuration/development
```
