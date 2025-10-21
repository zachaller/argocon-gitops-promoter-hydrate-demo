# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout afac0a63a5b861f2adfe22a5f7f2053dfc8d9c21
kustomize build ./user-configuration/production/us-west-1
```
