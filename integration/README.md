# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout cf8d632d7d6abf84dba00eb2e88d310db5f25b3e
kustomize build ./user-configuration/staging/integration
```
