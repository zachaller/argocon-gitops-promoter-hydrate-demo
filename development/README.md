# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 6dec7b9ae56b0efca02a60956f4a9e4dc53e5b01
kustomize build ./user-configuration/development
```
