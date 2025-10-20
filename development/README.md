# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 385bf7ec68c10e71400d68148e9c7726f9d8d203
kustomize build ./user-configuration/development
```
