# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 3c3fe31ba4e4b71c1986ae38e9152c6e5bed83a7
kustomize build ./user-configuration/staging/integration
```
