# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 2b374ccb9ce03952bc3c4eb203649fc6b8c2e5b6
kustomize build ./user-configuration/development
```
