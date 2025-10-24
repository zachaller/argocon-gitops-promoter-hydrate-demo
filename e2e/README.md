# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout d2bcb9bae36f855e39f6cfef6932dea43a6f5f69
kustomize build ./user-configuration/staging/e2e
```
