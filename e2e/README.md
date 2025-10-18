# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout af692c356c7589b5c16cee35121d496894a69c7d
kustomize build ./user-configuration/staging/e2e
```
