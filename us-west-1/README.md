# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout f7ce19f61fd502d5d8c6091a6e39e6aee8fa7e50
kustomize build ./user-configuration/production/us-west-1
```
