# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout fb2e1aee8f660561dc5d9c19a41f13af4df993d2
kustomize build ./user-configuration/development
```
