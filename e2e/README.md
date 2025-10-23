# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 8dc386e4803dac890a9a622c5176bfef3f245434
kustomize build ./user-configuration/staging/e2e
```
