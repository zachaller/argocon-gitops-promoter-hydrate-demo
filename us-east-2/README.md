# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 13dffb115f7f8af91ca0f2f313f48d9836ada76f
kustomize build ./user-configuration/production/us-east-2
```
