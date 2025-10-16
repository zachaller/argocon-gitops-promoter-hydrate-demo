# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout bea143e772bdeb15eb1767761ca284f6a6b8a16c
kustomize build ./user-configuration/staging/integration
```
