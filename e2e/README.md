# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 484c83e87fbd160f15432f826a5015c9568b42bf
kustomize build ./user-configuration/staging/e2e
```
