# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout aae4339cff16545c304ebb8baa278352984f232a
kustomize build ./user-configuration/staging/integration
```
