# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 7129f99a5bc8c84cd27208278fbd5c71ff03864c
kustomize build ./user-configuration/production/us-east-2
```
