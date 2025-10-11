# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 9d2d8275ab8a76b59454ab4505a3c04de280c2c9
kustomize build ./user-configuration/staging/integration
```
