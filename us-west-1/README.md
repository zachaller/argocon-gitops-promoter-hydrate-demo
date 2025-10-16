# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 7b5684eefe99fc758ef92fb6bd4cb37e954c928d
kustomize build ./user-configuration/production/us-west-1
```
