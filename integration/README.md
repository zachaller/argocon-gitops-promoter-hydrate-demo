# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout f071c7aa0ec419230f616247a4729f9976a5d346
kustomize build ./user-configuration/staging/integration
```
