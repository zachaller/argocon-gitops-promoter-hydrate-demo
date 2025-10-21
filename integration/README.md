# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout fbc0721206faab1bd555c553e9ffc6a562b40df9
kustomize build ./user-configuration/staging/integration
```
