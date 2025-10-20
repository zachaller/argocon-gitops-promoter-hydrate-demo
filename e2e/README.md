# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout cb181e4308b458b0543b2c92702a9a4fc895076e
kustomize build ./user-configuration/staging/e2e
```
