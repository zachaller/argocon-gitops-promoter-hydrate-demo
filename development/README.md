# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout d2bad8a41fbab189ab6d29949d8cf1858a700107
kustomize build ./user-configuration/development
```
