# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout a7419fdcde2100c47a2a2e053331c542aab51a44
kustomize build ./user-configuration/staging/integration
```
