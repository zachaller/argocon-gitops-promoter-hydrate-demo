# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 03f644e00c52729aad019b1a5e744df923011688
kustomize build ./user-configuration/staging/integration
```
