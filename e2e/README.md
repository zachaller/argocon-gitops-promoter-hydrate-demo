# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 1b188a8773ea9fddade9fb31138e11cb384b0863
kustomize build ./user-configuration/staging/e2e
```
