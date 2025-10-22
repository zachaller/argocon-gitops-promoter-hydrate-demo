# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout e9216dbb84e392f923c829193361334d9ba869fb
kustomize build ./user-configuration/staging/integration
```
