# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 4d6aa9026605fdefe5c0c96f622cdb8d78a1c727
kustomize build ./user-configuration/production/us-east-2
```
