# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 0f839bb51e1b27562325604cea555594a02f7265
kustomize build ./user-configuration/staging/e2e
```
