# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 6ceeb33200d1dcbb2d2a1cc50b33e7fc42b5460c
kustomize build ./user-configuration/staging/e2e
```
