# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 5b2ce4fa71cf337464a0d5bccb754fb8a6713255
kustomize build ./user-configuration/development
```
