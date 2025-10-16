# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout e77a099ea665dd7540a6aca9d00624132803fbb2
kustomize build ./user-configuration/development
```
