# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 6e67e92f500ba63a6c2c0d65e8e9c033537974b7
kustomize build ./user-configuration/staging/e2e
```
