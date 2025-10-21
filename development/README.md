# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 656286cea5c84609328d0fe31bb65cde29d9fdf2
kustomize build ./user-configuration/development
```
