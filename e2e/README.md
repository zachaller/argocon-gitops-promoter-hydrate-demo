# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 035c10bb2ccc3a81f790b5245c714518d51f7e46
kustomize build ./user-configuration/staging/e2e
```
