# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 632f708deee35b19777fcc4f754408f7e5c56fa1
kustomize build ./user-configuration/production/us-west-1
```
