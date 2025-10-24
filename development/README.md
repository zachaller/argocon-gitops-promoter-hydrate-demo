# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 7cd468409c8d6a086c0aa2b627fbaf544bba8bc1
kustomize build ./user-configuration/development
```
