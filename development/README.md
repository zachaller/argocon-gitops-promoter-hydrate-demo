# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 7cff2ebbb58571968a1d98780dc35af99b68aec1
kustomize build ./user-configuration/development
```
