# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 3ca2477704a3739b61203e4911b14aef16b98efb
kustomize build ./user-configuration/staging/integration
```
