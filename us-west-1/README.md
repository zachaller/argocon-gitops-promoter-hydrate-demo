# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 119d2132161aa1484f22166ca3347c86a83341cb
kustomize build ./user-configuration/production/us-west-1
```
