# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout decca6b447835931d6259e70984a05f1c34cfe29
kustomize build ./user-configuration/development
```
