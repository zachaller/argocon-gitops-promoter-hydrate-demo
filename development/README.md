# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 5649a3c13a119c812ed7098a9286b7178081ab22
kustomize build ./user-configuration/development
```
