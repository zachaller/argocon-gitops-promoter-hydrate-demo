# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 62f7f8a52b9a97b937f296e230f7b6f577ce8104
kustomize build ./user-configuration/staging/integration
```
