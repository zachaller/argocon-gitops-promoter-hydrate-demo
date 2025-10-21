# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 1edf6dc53c5c568dbf1b6ca94c5a8075e3163180
kustomize build ./user-configuration/staging/integration
```
