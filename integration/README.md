# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 16c1f2189eb39c60debf67c293cb7c51b2a644a3
kustomize build ./user-configuration/staging/integration
```
