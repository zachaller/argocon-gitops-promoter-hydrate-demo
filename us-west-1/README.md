# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout d30a472484639130defc81654113c57e0b362f8a
kustomize build ./user-configuration/production/us-west-1
```
