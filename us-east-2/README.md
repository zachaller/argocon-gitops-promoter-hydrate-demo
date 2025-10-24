# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout fa73d3ff1e0eeef13b9965d442535e4916c2f73d
kustomize build ./user-configuration/production/us-east-2
```
