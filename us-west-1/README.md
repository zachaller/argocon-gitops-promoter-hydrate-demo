# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 13512798680d9e047a776ada0fa47749def1e6ae
kustomize build ./user-configuration/production/us-west-1
```
