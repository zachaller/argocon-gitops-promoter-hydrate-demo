# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout afc88232c46c2d386634ed3572564b0d9009a230
kustomize build ./user-configuration/staging/integration
```
