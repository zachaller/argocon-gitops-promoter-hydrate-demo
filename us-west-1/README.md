# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 8a56726949295ed551875383b764b5e61e182aee
kustomize build ./user-configuration/production/us-west-1
```
