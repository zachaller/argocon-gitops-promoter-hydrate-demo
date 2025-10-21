# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 712d07fc0453e2d354b639a80d287266328fb607
kustomize build ./user-configuration/staging/integration
```
