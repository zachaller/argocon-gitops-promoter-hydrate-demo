# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout dbeb67b73e5b16332c04c0577cc1d1853ca6dcb3
kustomize build ./user-configuration/production/us-west-1
```
