# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout ccaea7d220e2f56de11112706ceb8a9cd12c8d50
kustomize build ./user-configuration/staging/integration
```
