# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 840888fe373a2ab328314fac4ba34c803b900110
kustomize build ./user-configuration/production/us-east-2
```
