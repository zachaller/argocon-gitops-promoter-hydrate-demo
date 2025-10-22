# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout f1b3471c1ae824533805ebd10e43f03618969967
kustomize build ./user-configuration/staging/integration
```
