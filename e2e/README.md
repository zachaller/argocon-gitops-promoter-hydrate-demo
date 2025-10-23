# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 944d7278a28113ca56220f2b62a10fc10ddb2adc
kustomize build ./user-configuration/staging/e2e
```
