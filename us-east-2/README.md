# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 9a2b10c99a3cd1598d680cff52142e3da8168417
kustomize build ./user-configuration/production/us-east-2
```
