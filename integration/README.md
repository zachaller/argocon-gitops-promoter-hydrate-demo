# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 94fc19391306ae27f00864d1c2584294879308d2
kustomize build ./user-configuration/staging/integration
```
