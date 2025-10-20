# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 1b5c712d3130dc0f5e661c8149973424187a03a4
kustomize build ./user-configuration/staging/e2e
```
