# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout d8f115cabbf6857afb8ba6aebc09f5ac2faf9651
kustomize build ./user-configuration/production/us-west-1
```
