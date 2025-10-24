# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 8274ef2c95cbecf82c191f767df1a8634ad0fe4f
kustomize build ./user-configuration/staging/e2e
```
