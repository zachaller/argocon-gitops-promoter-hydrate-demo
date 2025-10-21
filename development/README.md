# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout dd4fbb29bc645627a07a03da1e07a133b8c0ade3
kustomize build ./user-configuration/development
```
