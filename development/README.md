# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 5e29fe0923c94c9474eea632a4755195da3951ba
kustomize build ./user-configuration/development
```
