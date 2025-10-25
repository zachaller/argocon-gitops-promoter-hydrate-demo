# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 5e80b23731fd3238f98c61c8172fbca866085a50
kustomize build ./user-configuration/production/us-west-1
```
