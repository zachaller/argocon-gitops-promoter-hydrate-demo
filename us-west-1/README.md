# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout edf85e784c4c63e55f8e8b4f2153bf6fbc6f6e12
kustomize build ./user-configuration/production/us-west-1
```
