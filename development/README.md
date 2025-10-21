# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout b428c2ba93261782ca12cf92931f82aa81529cb1
kustomize build ./user-configuration/development
```
