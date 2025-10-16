# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 036b9c9588dffbf06619e978ecfd68471003e1ca
kustomize build ./user-configuration/staging/e2e
```
