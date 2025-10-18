# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout aa13a0690be57e1dc253d2d6bc82ee9d9d262386
kustomize build ./user-configuration/production/us-east-2
```
