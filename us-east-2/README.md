# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 760f43bd5612b9726cf257981e21b0df34c7e8b8
kustomize build ./user-configuration/production/us-east-2
```
