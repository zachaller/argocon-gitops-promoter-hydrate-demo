# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout a1a3da4773da8fffc9c635a65a223042b10ff5bc
kustomize build ./user-configuration/staging/e2e
```
