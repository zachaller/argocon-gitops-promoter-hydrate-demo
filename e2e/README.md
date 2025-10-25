# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout a73424b186e7c18a721a01a7668da8a7edcaed83
kustomize build ./user-configuration/staging/e2e
```
