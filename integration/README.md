# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 5b4bcc637871aa0a01d1ed9adbf511478577415c
kustomize build ./user-configuration/staging/integration
```
