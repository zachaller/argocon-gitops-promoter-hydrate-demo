# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout c31ff8569749ceb96dfdd1ce8ead1e96504293cd
kustomize build ./user-configuration/production/us-west-1
```
