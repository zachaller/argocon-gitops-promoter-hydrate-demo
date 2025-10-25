# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout a665695c47aa60e9b89821a0f30bbdde5bc0fe15
kustomize build ./user-configuration/staging/integration
```
