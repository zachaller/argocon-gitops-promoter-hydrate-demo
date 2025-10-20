# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout e3299556b07fae0cf2ff206bc40ee212678eda8a
kustomize build ./user-configuration/production/us-west-1
```
