# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 0215aba5a7672c7b9ea3d54aa15e27732f0ea1d3
kustomize build ./user-configuration/staging/integration
```
