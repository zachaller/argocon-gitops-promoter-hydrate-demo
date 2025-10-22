# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 988953378e3bc03c5fe83a28b11e564af8700e65
kustomize build ./user-configuration/staging/integration
```
