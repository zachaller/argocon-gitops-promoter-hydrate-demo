# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout c38a223bafeea1ea8ac1b104a7eee713d59f3978
kustomize build ./user-configuration/staging/integration
```
