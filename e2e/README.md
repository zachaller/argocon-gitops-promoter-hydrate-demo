# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 52d86a23d0996ab7ec5d9ee70854dad02b410778
kustomize build ./user-configuration/staging/e2e
```
