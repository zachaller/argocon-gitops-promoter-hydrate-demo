# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 86f77a1f8b7c1e9981a3546ed54551135a6ce6c0
kustomize build ./user-configuration/production/us-west-1
```
