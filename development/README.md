# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 684045b23c2ebc8b5d6d1aa9fb8e6d7f551422f1
kustomize build ./user-configuration/development
```
