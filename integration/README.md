# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 32917abbe929e6d66cb8be7254ac53200b24a5a6
kustomize build ./user-configuration/staging/integration
```
