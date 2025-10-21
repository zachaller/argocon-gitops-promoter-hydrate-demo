# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 6dfd2e1cb37c4e44815fa13e1a749e647c258cc2
kustomize build ./user-configuration/development
```
