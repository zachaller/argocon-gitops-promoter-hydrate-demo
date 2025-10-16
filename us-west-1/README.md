# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout d77b96839c534b4c44409776084386a914d800c0
kustomize build ./user-configuration/production/us-west-1
```
