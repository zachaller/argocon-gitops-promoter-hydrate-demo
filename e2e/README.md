# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout de95a7beb1ba5e43bb26a1a1e6dd2e309f04c4a0
kustomize build ./user-configuration/staging/e2e
```
