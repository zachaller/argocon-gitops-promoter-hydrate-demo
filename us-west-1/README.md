# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout b3c111e3381ed50e7f0213c8d2ca429c3ff8dc34
kustomize build ./user-configuration/production/us-west-1
```
