# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 5dccb4a3926c13a204b2a2b9a29045289aec3427
kustomize build ./user-configuration/staging/integration
```
