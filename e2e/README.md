# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 302eebd95eb5b96bb672dc8d54bfa5f074eb9da0
kustomize build ./user-configuration/staging/e2e
```
