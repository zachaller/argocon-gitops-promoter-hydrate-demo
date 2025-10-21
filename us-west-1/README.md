# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 02f12784dbd84d97eff84d127582abe4eb34b753
kustomize build ./user-configuration/production/us-west-1
```
