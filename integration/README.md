# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 4680d7a60fdfbd75ac7875fa6f66068db2c26dbc
kustomize build ./user-configuration/staging/integration
```
