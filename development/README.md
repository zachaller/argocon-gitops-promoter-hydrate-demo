# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 5e29a328b9c987221bd3982491973b3720f573b5
kustomize build ./user-configuration/development
```
