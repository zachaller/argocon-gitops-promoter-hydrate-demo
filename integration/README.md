# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 0c1d87c80416b79bef3ece4ac003ccb75c3f387a
kustomize build ./user-configuration/staging/integration
```
