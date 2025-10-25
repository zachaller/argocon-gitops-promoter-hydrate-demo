# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout dda41b19397b7e66b69bdf5dcea78ed32441beae
kustomize build ./user-configuration/staging/e2e
```
