# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout d8cb654fc350d3c5c58f3a3f971bb256d04c87aa
kustomize build ./user-configuration/production/us-east-2
```
