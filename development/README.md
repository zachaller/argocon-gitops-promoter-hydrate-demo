# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 709fa648334cbf2faa942a8fa86fc919b2bf0b80
kustomize build ./user-configuration/development
```
