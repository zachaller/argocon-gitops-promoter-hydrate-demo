# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 8981c84877b2c25ba32d1e512eea40ac185a1d39
kustomize build ./user-configuration/development
```
