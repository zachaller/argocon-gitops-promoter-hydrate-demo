# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 326bc44bd01abd6c1855808ff6028df41c8f862c
kustomize build ./user-configuration/production/us-east-2
```
