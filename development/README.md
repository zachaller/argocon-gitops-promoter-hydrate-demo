# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout c24449b85bd3dc2182903e16ee60304bf7d6ff16
kustomize build ./user-configuration/development
```
