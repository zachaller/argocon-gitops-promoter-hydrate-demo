# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 66faf2ceda6140e3a1e84a124718dba66c41eaed
kustomize build ./user-configuration/staging/integration
```
