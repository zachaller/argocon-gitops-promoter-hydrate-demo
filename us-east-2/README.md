# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout a306dcae7933b7eeb83de3617125ac216d3c231e
kustomize build ./user-configuration/production/us-east-2
```
