# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 5d3afa44ab39fecd8d037808add59138df203be4
kustomize build ./user-configuration/staging/integration
```
