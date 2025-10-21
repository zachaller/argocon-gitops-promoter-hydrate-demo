# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout c55245e25c276ce7aa1b784ba3a3b6093a55b062
kustomize build ./user-configuration/development
```
