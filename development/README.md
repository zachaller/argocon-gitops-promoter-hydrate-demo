# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout f87c469a65808c6f7013aaddbcf7bf98918178ff
kustomize build ./user-configuration/development
```
