# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 916dab150af384eda0faf675d5c1bfe3c481b640
kustomize build ./user-configuration/production/us-west-1
```
