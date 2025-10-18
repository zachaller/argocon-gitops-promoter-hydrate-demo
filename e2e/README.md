# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 0b880e24cd9efcf71608f2d87066a5e26e21de44
kustomize build ./user-configuration/staging/e2e
```
