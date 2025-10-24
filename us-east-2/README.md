# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout a67bdd99d58c8425b9e7ed5b5d6c3d9a903e1ea5
kustomize build ./user-configuration/production/us-east-2
```
