# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 746f5292618cb017f4ca128fdb7f0a90447d7022
kustomize build ./user-configuration/development
```
