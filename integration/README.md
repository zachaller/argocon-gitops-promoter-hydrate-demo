# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout ca76fa16f8beaaa884ef3152e5b7d0344b8f788a
kustomize build ./user-configuration/staging/integration
```
