# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 7fe44579f3e09f06ba814f1403812ff591d63ace
kustomize build ./user-configuration/staging/integration
```
