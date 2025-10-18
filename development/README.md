# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 9e37b6764b0cb5ae638e017f6bf8d94e4e333ef5
kustomize build ./user-configuration/development
```
