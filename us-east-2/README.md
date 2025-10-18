# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 78ada0138d8850a52eacc5fcbae021eba88c06e5
kustomize build ./user-configuration/production/us-east-2
```
