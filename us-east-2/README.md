# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 990b9675b8e9487b5af718c13c914f5d86d9c902
kustomize build ./user-configuration/production/us-east-2
```
