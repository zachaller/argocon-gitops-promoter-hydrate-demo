# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout ee47673fa1c261263503cfd3be0c4dd0956f6067
kustomize build ./user-configuration/staging/e2e
```
