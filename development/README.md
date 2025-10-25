# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout e1983112e602b6098c372eb466a808a066c279d2
kustomize build ./user-configuration/development
```
