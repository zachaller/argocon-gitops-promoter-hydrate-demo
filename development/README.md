# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 7f82dbf65793c2d0553fbd9b0e7e3fc528278d95
kustomize build ./user-configuration/development
```
