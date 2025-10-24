# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 8d25eb1a73d88a168fcb12435b7f065c6afe6a89
kustomize build ./user-configuration/production/us-west-1
```
