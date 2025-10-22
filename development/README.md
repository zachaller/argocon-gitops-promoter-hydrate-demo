# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 59bf67dad17eb5d1d38f62d28725d7d3cbfa143f
kustomize build ./user-configuration/development
```
