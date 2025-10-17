# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 6179cc3deb2896e7650f3d1212ff5fcc2fcee33f
kustomize build ./user-configuration/staging/integration
```
