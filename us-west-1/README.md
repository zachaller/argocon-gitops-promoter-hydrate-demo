# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 21e98d18128990d3d733e1339db52e2fdad9fa65
kustomize build ./user-configuration/production/us-west-1
```
