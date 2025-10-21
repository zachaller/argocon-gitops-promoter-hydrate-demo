# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout d1f277ba17a2f9f6d856fc4e678955f546db10af
kustomize build ./user-configuration/production/us-west-1
```
