# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 0a85453d0aca0c451c04dd814898f0a248400bba
kustomize build ./user-configuration/staging/integration
```
