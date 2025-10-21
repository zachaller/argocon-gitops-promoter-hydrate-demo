# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 612748445961ac13c083e0ff09a4bdd932706dfd
kustomize build ./user-configuration/staging/e2e
```
