# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout f18cd149261b1c675493ab3fb46370897cac24ae
kustomize build ./user-configuration/staging/e2e
```
