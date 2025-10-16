# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout b43718d24f27fb27911e4728d22631b6c9790f52
kustomize build ./user-configuration/staging/integration
```
