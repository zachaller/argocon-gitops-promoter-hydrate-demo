# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 8e81c82f459e7ff777719c47dbf2e5fcbb973c57
kustomize build ./user-configuration/production/us-west-1
```
