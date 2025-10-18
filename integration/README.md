# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout f054cabab005090fadf366923dd57012f73607ce
kustomize build ./user-configuration/staging/integration
```
