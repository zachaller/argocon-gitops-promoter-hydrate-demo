# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout ba22c4b10c40bd5b0bf53d5bcafcd5eafd2add76
kustomize build ./user-configuration/staging/e2e
```
