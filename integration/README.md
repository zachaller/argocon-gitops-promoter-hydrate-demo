# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout fefcf9dce7419958c8c927be30c5a44d7e28e6d6
kustomize build ./user-configuration/staging/integration
```
