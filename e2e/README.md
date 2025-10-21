# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout aa214ea2fe62c11659738c1f1842d9285e3bbd76
kustomize build ./user-configuration/staging/e2e
```
