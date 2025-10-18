# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout d5c59d501f5a74ae790061e4d1647943c071899d
kustomize build ./user-configuration/development
```
