# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 67f4aebffe250c25749956746851e0ef7a0c21e0
kustomize build ./user-configuration/staging/integration
```
