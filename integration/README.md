# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout dddc8d13902cb09483bec1bc9fabfef285e11d77
kustomize build ./user-configuration/staging/integration
```
