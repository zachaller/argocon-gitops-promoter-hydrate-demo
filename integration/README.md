# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout b1e5d78d80c28ccb7f76fd3bd6764bccf2b963b7
kustomize build ./user-configuration/staging/integration
```
