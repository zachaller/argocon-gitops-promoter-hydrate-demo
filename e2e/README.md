# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout b1b01777ede7c3aa680fdc998f98c7f482f9bb93
kustomize build ./user-configuration/staging/e2e
```
