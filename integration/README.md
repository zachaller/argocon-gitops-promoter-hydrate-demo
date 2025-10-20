# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 30ba5729a382868f704d45f0df72f4ea0291b117
kustomize build ./user-configuration/staging/integration
```
