# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout eaa951689d3320b939eab798eacb8959732ad8c8
kustomize build ./user-configuration/staging/e2e
```
