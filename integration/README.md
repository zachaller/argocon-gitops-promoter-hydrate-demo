# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 8f4aee1ef878ab3b1ef680465faa63f45bf69eab
kustomize build ./user-configuration/staging/integration
```
