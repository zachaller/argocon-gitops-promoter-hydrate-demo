# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 51db177e35d4f64f5d0efa980d3d7afd7d7f0117
kustomize build ./user-configuration/staging/e2e
```
