# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 954bc67f86ebc1f58267c7fcb1420137e1f1b578
kustomize build ./user-configuration/staging/e2e
```
