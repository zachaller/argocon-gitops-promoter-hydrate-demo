# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 2ebe1f91a62886dc5731978ea38add65ed89e6e4
kustomize build ./user-configuration/development
```
