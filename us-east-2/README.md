# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout b2aefa75cde960334357f643cdadf1ed1514050c
kustomize build ./user-configuration/production/us-east-2
```
