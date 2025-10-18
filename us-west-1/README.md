# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 1e8b09600b015b8bcdd5888195ada888b8143258
kustomize build ./user-configuration/production/us-west-1
```
