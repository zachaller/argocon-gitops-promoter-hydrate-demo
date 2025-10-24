# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 57aea570a5d240ccfe4aa4d08cffcbc3d87f9923
kustomize build ./user-configuration/development
```
