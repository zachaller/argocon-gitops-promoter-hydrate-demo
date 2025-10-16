# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout d8c0372da1e3b8df12674e4b239ec3a4802e88ec
kustomize build ./user-configuration/staging/e2e
```
