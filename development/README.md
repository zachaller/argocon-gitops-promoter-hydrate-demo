# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout f5b2cc5014358e8580febc484d8a9650ff2fcf9c
kustomize build ./user-configuration/development
```
