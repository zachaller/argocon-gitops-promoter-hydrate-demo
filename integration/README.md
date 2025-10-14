# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 1f1c22dcd850299416cc1bd8bbcd3f419cde3a02
kustomize build ./user-configuration/staging/integration
```
