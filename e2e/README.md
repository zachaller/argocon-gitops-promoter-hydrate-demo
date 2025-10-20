# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 5afafa4dcff2cb8e386b63782b87dffd464e282e
kustomize build ./user-configuration/staging/e2e
```
