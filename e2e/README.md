# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 433b2a12e22a3ec0ca087c4a98de95191900a3e4
kustomize build ./user-configuration/staging/e2e
```
