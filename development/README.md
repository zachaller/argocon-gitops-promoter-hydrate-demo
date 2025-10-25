# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout b3fd5b7fd63be6258ff39511756ff5ff0e48aa96
kustomize build ./user-configuration/development
```
