# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 95377f90b46f1e7100d7e9cc65dce0dee37a1ff8
kustomize build ./user-configuration/staging/e2e
```
