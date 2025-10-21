# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout f3896b2f55fd96971896373b31e944113542cc9e
kustomize build ./user-configuration/production/us-west-1
```
