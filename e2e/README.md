# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout d01b381308e3c37824b221d281d17b5228c90625
kustomize build ./user-configuration/staging/e2e
```
