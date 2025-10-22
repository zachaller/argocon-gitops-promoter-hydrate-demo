# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout d886f03a70a1591f6037d546f1f9662b479163cc
kustomize build ./user-configuration/staging/e2e
```
