# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 7e0d7844514ed5a0e5bef4dc870e59d56f64ddd1
kustomize build ./user-configuration/development
```
