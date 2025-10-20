# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 8061eb2e4306e4da1031dea7aed913b2d0f16c24
kustomize build ./user-configuration/development
```
