# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout a3b5ca7394ef51a31d911307b92f7d0d4e798a8d
kustomize build ./user-configuration/production/us-west-1
```
