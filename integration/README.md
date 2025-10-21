# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout dc860139d25803a41fb5a85d150818448d31dd67
kustomize build ./user-configuration/staging/integration
```
