# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout ca036f93754a346efb0d37320bf02896a2cc1d79
kustomize build ./user-configuration/staging/e2e
```
