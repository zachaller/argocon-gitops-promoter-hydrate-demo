# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 0ae0f09ea3cb9bba940215eee4bc131f51c529b4
kustomize build ./user-configuration/development
```
