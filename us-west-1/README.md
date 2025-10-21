# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout d2ac9fe79b8cf44f3f21909a6d7f994dd249e566
kustomize build ./user-configuration/production/us-west-1
```
