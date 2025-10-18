# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout df369c8f5d7bbf1e34c332506cda724a16f363a7
kustomize build ./user-configuration/production/us-east-2
```
