# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 8a33911d3f4c992e7977c9b748ec1b02d40a7e6f
kustomize build ./user-configuration/production/us-west-1
```
