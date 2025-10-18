# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 6e084e5a8ef760300150b01bbf7b8a7ca1b667d6
kustomize build ./user-configuration/development
```
