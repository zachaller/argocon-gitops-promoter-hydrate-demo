# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 19a18f3a66e4bb0105134b2fb92e9caca18d2ffd
kustomize build ./user-configuration/production/us-west-1
```
