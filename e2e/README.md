# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 1113cee1a158b2501039c689aaf96205cbe8c576
kustomize build ./user-configuration/staging/e2e
```
