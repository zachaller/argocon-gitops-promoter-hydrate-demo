# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 5933514c44c592af500f96b5d5cd76491b44c46f
kustomize build ./user-configuration/staging/integration
```
