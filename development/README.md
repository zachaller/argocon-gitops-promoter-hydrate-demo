# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 6b5063db8e6c190e4007049630dc9639395c751d
kustomize build ./user-configuration/development
```
