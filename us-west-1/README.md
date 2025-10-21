# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 24797616b27f628d8dff908fe8d4d8e5b10b17a3
kustomize build ./user-configuration/production/us-west-1
```
