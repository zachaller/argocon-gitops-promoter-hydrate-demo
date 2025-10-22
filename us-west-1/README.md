# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout b3d0b3c0ea9e31ab27a72e3fe8d24e2f1e013e0a
kustomize build ./user-configuration/production/us-west-1
```
