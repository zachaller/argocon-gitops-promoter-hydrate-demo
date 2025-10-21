# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 492bde409ecbc89caf6e5c4494fa0a693b9b83de
kustomize build ./user-configuration/staging/e2e
```
