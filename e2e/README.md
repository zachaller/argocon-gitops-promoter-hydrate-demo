# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout fac003beb5f822703df9f11b98e184229a548d06
kustomize build ./user-configuration/staging/e2e
```
