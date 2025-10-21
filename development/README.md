# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout f4fdee1e67efd6365e148500d765d68c47474833
kustomize build ./user-configuration/development
```
