# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout f62c9aa34dcfe2c410849f082519cf11b2ff1192
kustomize build ./user-configuration/production/us-west-1
```
