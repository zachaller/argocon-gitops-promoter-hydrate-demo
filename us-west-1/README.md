# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 6d7ffcf47299c733ca9cc9c01ddda54a40b48dfe
kustomize build ./user-configuration/production/us-west-1
```
