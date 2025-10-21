# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout ae2744095fcf9eecc46f03383c8072d5047c3f5e
kustomize build ./user-configuration/production/us-west-1
```
