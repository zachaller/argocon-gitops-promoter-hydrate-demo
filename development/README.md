# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout dc676ebfab9231fa4156897ce28e92322429c723
kustomize build ./user-configuration/development
```
