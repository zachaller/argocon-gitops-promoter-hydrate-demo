# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 6af386a5bd2cfc78cd4c21c9758642784f579251
kustomize build ./user-configuration/staging/e2e
```
