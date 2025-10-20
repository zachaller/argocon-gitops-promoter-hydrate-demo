# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 9f19b20c83b6a1100c7cff22c81809b7e49971d6
kustomize build ./user-configuration/staging/integration
```
