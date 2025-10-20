# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 72c6177842afdcb551d5f5ebae78793e2f335af6
kustomize build ./user-configuration/development
```
