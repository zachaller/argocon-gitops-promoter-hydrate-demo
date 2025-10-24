# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout ebb34fb321c88a78a2738e219d765e443b2caec8
kustomize build ./user-configuration/development
```
