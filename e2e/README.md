# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 5adaa9849eb43cdd980a89d5ad828b0d634eff15
kustomize build ./user-configuration/staging/e2e
```
