# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 4a244f6309509a9360d6772071e4ed8898d856f9
kustomize build ./user-configuration/production/us-east-2
```
