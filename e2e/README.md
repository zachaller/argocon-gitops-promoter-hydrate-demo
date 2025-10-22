# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 29c6c42d7533f843a7a7cb89fdbbc02e51a0389d
kustomize build ./user-configuration/staging/e2e
```
