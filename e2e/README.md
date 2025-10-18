# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 3c42f5a4870309b1659058a8e0c1143383d25042
kustomize build ./user-configuration/staging/e2e
```
