# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout fce7e351d5eb66ae15eb5f46eac6dfbade5dc49c
kustomize build ./user-configuration/staging/e2e
```
