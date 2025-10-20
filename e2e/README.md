# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 6c3127554dbc3a4f6a4694f61f31ab7cdeb7fc3d
kustomize build ./user-configuration/staging/e2e
```
