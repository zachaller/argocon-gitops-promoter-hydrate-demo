# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 01a61310395236e5fd8423c566e9c8acdf4944a1
kustomize build ./user-configuration/production/us-west-1
```
