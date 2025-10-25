# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 778779e85aed1d7f94e1832de581b79c1f8c1c68
kustomize build ./user-configuration/staging/integration
```
