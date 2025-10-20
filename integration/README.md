# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 7b7beaba34fed252bb13a582272e15773eb19acc
kustomize build ./user-configuration/staging/integration
```
