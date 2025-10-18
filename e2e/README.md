# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout f61da31002918a702299789decf4ebd3f1213967
kustomize build ./user-configuration/staging/e2e
```
