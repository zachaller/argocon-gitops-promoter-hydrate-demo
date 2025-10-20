# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 25e9cfe835b2c2ec82a8557519d57059d635869d
kustomize build ./user-configuration/development
```
