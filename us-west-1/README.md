# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 586fae369788bd81c426f6384afb43e5ca801c8b
kustomize build ./user-configuration/production/us-west-1
```
