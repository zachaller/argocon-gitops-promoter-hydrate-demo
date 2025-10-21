# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 9be3ad36c6733d2b0dc286cfd70a316a0fd8aa4f
kustomize build ./user-configuration/production/us-west-1
```
