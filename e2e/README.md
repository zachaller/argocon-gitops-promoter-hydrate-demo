# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout de4b9d5adb04da66be80775383d0f9e26516a0a0
kustomize build ./user-configuration/staging/e2e
```
