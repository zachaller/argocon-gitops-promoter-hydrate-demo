# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 58732a266ad23839169f1bb5e0b2a90cdbea1329
kustomize build ./user-configuration/staging/integration
```
