# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 8b82ab40b804f6c1b3c2d37868ecdbe8d2942982
kustomize build ./user-configuration/production/us-west-1
```
