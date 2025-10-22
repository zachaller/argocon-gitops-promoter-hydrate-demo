# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 976a3d36dfb9e0fd163dfcdc38b610e824728baa
kustomize build ./user-configuration/production/us-east-2
```
