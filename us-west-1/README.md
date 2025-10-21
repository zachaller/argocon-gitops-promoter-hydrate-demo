# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout c02c5af6e4bdb9a99a31e34cc4c314a32bec9b2f
kustomize build ./user-configuration/production/us-west-1
```
