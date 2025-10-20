# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 80e4cf6273e23b2d616f59a511796315c7ab1143
kustomize build ./user-configuration/development
```
