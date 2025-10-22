# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 8df52deb5afc105767f8cdc355f99b785a2f025d
kustomize build ./user-configuration/staging/integration
```
