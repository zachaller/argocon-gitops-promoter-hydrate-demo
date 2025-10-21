# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 8f8b8a6f8b4b478d28e5c88d255008d01c75ed50
kustomize build ./user-configuration/staging/e2e
```
