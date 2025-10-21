# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 206dc6a3e61526cea4760094b702e639efa3c6db
kustomize build ./user-configuration/production/us-west-1
```
