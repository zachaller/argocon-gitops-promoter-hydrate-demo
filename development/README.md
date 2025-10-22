# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout b88950f8780512c5a2b9a681ab3bf80a804fc1f1
kustomize build ./user-configuration/development
```
