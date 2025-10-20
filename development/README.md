# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout c45e6241211dc26d3ffff46559ea106ad58c588d
kustomize build ./user-configuration/development
```
