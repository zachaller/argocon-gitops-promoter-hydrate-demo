# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout b9a62b2dcdb3d494ff348c4c4220ed8af0b8ed3b
kustomize build ./user-configuration/staging/integration
```
