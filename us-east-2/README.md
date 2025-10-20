# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 78da272bda096e437125ba9198de8ddc82fc640a
kustomize build ./user-configuration/production/us-east-2
```
