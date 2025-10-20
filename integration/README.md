# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 8167475ac3ff64d1c9b1872fbe8aae65fc4e6fd2
kustomize build ./user-configuration/staging/integration
```
