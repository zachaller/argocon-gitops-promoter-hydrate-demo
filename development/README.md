# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 6b77706a5ba51645a9dc6f4335ffd32afd65d3a0
kustomize build ./user-configuration/development
```
