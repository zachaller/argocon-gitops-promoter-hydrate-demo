# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 8bad730e8ecbabb0b56b9a6ee522c29eb54a4a61
kustomize build ./user-configuration/staging/e2e
```
