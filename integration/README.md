# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 53e320cdd3b7a63932e2c1960c168b2bd0b1f64d
kustomize build ./user-configuration/staging/integration
```
