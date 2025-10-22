# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 3c225f8da5cf48338d0d64f1e83faf13c978fa3c
kustomize build ./user-configuration/staging/e2e
```
