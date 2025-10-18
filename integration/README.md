# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout c4a578bb38bd7c4469ad8633dd4fd732b1a14a29
kustomize build ./user-configuration/staging/integration
```
