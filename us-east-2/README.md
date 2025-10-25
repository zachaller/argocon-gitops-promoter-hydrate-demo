# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout fe3ab830307bb1cd4b951784e6290c7348c179d2
kustomize build ./user-configuration/production/us-east-2
```
