# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 7c641d06476b5cb68d600536036285c6a8d43e10
kustomize build ./user-configuration/staging/integration
```
