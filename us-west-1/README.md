# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 3fa341e2e9fd4d69bf8b5ef17e20a4b5fdcaa0af
kustomize build ./user-configuration/production/us-west-1
```
