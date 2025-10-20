# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 0f9ac84b16c4ee3103062da2063edb178eb70a52
kustomize build ./user-configuration/staging/integration
```
