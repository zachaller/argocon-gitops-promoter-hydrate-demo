# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 5b08ebb2f1773a9b4b19a9abd1409f40b68845bb
kustomize build ./user-configuration/development
```
