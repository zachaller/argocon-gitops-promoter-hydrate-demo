# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 81d7c7f8b7f75952fadefc9b45a1c914e6217de3
kustomize build ./user-configuration/development
```
