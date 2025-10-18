# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout fa0373555d682315647b05dece7e7d462817bef0
kustomize build ./user-configuration/staging/integration
```
