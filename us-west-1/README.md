# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 472aee5d298bb4227c90d05f97c883b011a46caf
kustomize build ./user-configuration/production/us-west-1
```
