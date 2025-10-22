# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout deb72ba789fe286b9fa9e0c0e2594ab17dba9b41
kustomize build ./user-configuration/staging/integration
```
