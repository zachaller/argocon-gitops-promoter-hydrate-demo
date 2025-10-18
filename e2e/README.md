# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 3f540fcf8845448fcdcc140728062267fd92fdb7
kustomize build ./user-configuration/staging/e2e
```
