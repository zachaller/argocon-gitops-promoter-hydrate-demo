# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout f15163aeb96f65f0ffc94b877c3eee53ad12c2b8
kustomize build ./user-configuration/staging/e2e
```
