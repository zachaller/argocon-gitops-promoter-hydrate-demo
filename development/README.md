# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 4b78d5f402cbfae360e6222bc85ae85bf43f62d1
kustomize build ./user-configuration/development
```
