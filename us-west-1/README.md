# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout ac7f2e153f9e28291f1ce964b46cb6ddf73d1520
kustomize build ./user-configuration/production/us-west-1
```
