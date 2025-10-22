# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout f7f14fe700ef678c7e208c27c6055ad5e4c945e7
kustomize build ./user-configuration/production/us-west-1
```
