# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout a8691adf5941136e9b88fc1f285dabefbbe9782c
kustomize build ./user-configuration/development
```
