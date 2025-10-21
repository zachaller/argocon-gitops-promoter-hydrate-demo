# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 7316d6044c2a1bc3813acaaf790663f73761b15f
kustomize build ./user-configuration/production/us-west-1
```
