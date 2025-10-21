# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout fede8eac8995151160f977efe59e82c6e516b9d2
kustomize build ./user-configuration/staging/e2e
```
