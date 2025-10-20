# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout ae529d928984a64eb90fe077f3d567786f5a88d6
kustomize build ./user-configuration/production/us-west-1
```
