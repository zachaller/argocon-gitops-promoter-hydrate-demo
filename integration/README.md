# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 4d751ac844055f9d3f109f94576a3cc0485bea7c
kustomize build ./user-configuration/staging/integration
```
