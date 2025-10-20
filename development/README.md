# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout f8eeb55ba1ce6c420624e5d2afc66c93ee889bd1
kustomize build ./user-configuration/development
```
