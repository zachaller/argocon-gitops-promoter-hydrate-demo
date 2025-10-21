# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout d1968189d3370b272156ab61f22e67605aafd378
kustomize build ./user-configuration/staging/integration
```
