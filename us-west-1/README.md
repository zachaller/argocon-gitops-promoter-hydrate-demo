# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 148a697bbda568a5a07eb44eeaa54002a641f14c
kustomize build ./user-configuration/production/us-west-1
```
