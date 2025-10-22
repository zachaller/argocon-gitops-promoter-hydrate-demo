# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 7f66d4494a4f487031d10e20bb3a648755d4ba5d
kustomize build ./user-configuration/staging/e2e
```
