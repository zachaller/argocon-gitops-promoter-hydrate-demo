# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout a37be8571a6fd1cf6e1252c22d62925f139f7e14
kustomize build ./user-configuration/production/us-west-1
```
