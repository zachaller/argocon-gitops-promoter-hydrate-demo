# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 2ce5e00fcd6b9ed9df9d51fe5761a8a75529ab78
kustomize build ./user-configuration/production/us-west-1
```
