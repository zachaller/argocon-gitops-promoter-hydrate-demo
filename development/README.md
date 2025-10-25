# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 01872420cf48cd85a14450dfdf9b742f14b79d66
kustomize build ./user-configuration/development
```
