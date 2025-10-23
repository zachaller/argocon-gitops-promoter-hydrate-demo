# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 9dd086f0c797a99efa4c0d1125561cd16f0fce51
kustomize build ./user-configuration/staging/e2e
```
