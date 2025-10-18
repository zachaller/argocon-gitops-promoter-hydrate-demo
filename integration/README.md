# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 5e962a8beba0b68cb15a4d3172bae5fc6a4dd951
kustomize build ./user-configuration/staging/integration
```
