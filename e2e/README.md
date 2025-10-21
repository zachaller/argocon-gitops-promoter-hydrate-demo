# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 31604a53a534c2a59096148b5833f6a85b7a1296
kustomize build ./user-configuration/staging/e2e
```
