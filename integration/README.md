# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 350f1ce9492a91b65c5fedffca5e6577f863a9fd
kustomize build ./user-configuration/staging/integration
```
