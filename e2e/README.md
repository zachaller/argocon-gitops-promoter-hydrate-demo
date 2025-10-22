# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 0b05fac7c87173bc3b95c5d67c2eb1469b847833
kustomize build ./user-configuration/staging/e2e
```
