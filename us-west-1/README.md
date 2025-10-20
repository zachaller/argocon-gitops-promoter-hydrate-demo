# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 6b2bc2fe7d2319b992647558ea5d8275091154a4
kustomize build ./user-configuration/production/us-west-1
```
