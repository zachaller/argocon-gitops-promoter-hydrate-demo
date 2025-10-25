# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 38a0b318e4aac4e7b08f54c233bf4b9da5a9816c
kustomize build ./user-configuration/development
```
