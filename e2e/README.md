# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 30c49497d2fdd2eeda8da607a7c43a5c7fae999f
kustomize build ./user-configuration/staging/e2e
```
