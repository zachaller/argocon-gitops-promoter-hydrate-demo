# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 010390e41b9dd17c593013a5e372bc4a4e74b4c4
kustomize build ./user-configuration/staging/e2e
```
