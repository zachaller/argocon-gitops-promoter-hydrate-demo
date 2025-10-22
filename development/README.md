# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 56a37202dfbbea03846f632ca1ef74bafd8efb33
kustomize build ./user-configuration/development
```
