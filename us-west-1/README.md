# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout c122034bfb52c3e3ceeb66f004b1642ba2c4107b
kustomize build ./user-configuration/production/us-west-1
```
