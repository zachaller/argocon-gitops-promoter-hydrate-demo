# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 32713ec478884177ed7e2d86b99eba1b4e0c7f10
kustomize build ./user-configuration/production/us-west-1
```
