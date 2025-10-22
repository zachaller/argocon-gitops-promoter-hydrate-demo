# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 621e3ce430431954fdcf6c11e6f1158ae211973e
kustomize build ./user-configuration/production/us-west-1
```
