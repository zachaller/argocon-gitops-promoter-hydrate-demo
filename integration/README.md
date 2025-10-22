# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout d081e0c28e4b905de026a597ea1ca5114f7f0310
kustomize build ./user-configuration/staging/integration
```
