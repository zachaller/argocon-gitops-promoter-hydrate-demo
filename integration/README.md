# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout d23491b52ebbd7badfff22f695fefb1470840a75
kustomize build ./user-configuration/staging/integration
```
