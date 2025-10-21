# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout dfa6893bcf616da366e7b2b9bd3f46a65f44fb2e
kustomize build ./user-configuration/staging/e2e
```
