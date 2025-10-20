# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 0bda27962d5f74730eda5d57774434e0a3273cfa
kustomize build ./user-configuration/production/us-west-1
```
