# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 094c2895e57378a4e96533a699e40c7e8d503422
kustomize build ./user-configuration/staging/e2e
```
