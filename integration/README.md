# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 77051deef1b9dcdbd75797e50fa20ab0d0c2fc36
kustomize build ./user-configuration/staging/integration
```
