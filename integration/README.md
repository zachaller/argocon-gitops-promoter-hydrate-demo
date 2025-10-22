# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 14b687676cdbcd1100945fe8628356c9ab78ffb8
kustomize build ./user-configuration/staging/integration
```
