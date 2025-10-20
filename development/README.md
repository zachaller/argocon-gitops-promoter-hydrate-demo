# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout f1b951769eaf780af9b8c60b2095cfa8f20cbdb9
kustomize build ./user-configuration/development
```
