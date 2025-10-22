# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 1955274453996b11440f6f3324683138ceacc50d
kustomize build ./user-configuration/staging/integration
```
