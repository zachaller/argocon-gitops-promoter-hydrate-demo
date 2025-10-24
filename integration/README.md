# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout b4f81d1621b4927392f6aa240a674de8dd23f71c
kustomize build ./user-configuration/staging/integration
```
