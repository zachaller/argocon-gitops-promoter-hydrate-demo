# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout cc000159593ac30765b8d5dc4ade740509c6b19f
kustomize build ./user-configuration/staging/integration
```
