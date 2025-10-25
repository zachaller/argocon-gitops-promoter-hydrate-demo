# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 018352995670740fd41bd7c684c24a995bbeb0d9
kustomize build ./user-configuration/staging/integration
```
