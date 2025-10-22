# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 69254833119caf75ba20b9fd2bafbce359d24eb2
kustomize build ./user-configuration/development
```
