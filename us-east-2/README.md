# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 52f70d25f9784d1831a31cd8788f3f969a0e0255
kustomize build ./user-configuration/production/us-east-2
```
