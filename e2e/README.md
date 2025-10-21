# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout eedf72048920281f1f042e4e43fc428ba8b97dc8
kustomize build ./user-configuration/staging/e2e
```
