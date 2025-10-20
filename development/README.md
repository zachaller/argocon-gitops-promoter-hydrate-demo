# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout b7bd079f414eda317659503d960cc6cd228da6c0
kustomize build ./user-configuration/development
```
