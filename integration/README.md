# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout a034d2dea3f24a32831fe0dfeb06ca4feca18a38
kustomize build ./user-configuration/staging/integration
```
