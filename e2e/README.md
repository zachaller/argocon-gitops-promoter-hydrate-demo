# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 8d9258e1048985edb24594d8cd00f8fd095a6c68
kustomize build ./user-configuration/staging/e2e
```
