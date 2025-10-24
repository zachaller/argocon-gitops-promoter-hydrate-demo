# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout e208b6bf591cf1f4960c258a0b4e07f8244e030e
kustomize build ./user-configuration/production/us-west-1
```
