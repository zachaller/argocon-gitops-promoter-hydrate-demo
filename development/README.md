# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 38241cbaca808b1556a893a889f39613c2d43e31
kustomize build ./user-configuration/development
```
