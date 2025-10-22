# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 84b49df17882d2012e0dd1d6c7f71ac064448fa8
kustomize build ./user-configuration/production/us-east-2
```
