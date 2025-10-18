# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 7721c4801bed4840f1a8345c4da8428145bba995
kustomize build ./user-configuration/development
```
