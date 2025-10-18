# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 7f5dd2cca8b05768991f511210d2cb81278c58f0
kustomize build ./user-configuration/development
```
