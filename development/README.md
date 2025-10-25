# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout ce3720b2507b5ed9fa55c4197a24d910ef44ee17
kustomize build ./user-configuration/development
```
