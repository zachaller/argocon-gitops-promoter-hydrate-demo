# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 2d7fc624dfe2326959730401efebf9637082e215
kustomize build ./user-configuration/production/us-east-2
```
