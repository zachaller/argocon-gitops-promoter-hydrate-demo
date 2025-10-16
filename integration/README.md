# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout f60fc983c7671412dca3449ae291315d9cccbf71
kustomize build ./user-configuration/staging/integration
```
