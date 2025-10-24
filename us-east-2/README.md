# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 8d8827940ef1d3416d08dbfff8b1695134eedca3
kustomize build ./user-configuration/production/us-east-2
```
