# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 7098100aae830c0860b542b2f53d9903cbb7d851
kustomize build ./user-configuration/development
```
