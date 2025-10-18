# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 6eadec521d8621599246a8503d9c655ac45a66a5
kustomize build ./user-configuration/development
```
