# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 1e3c8f867d73ab7ab0b2a86477aa81810384e7a2
kustomize build ./user-configuration/staging/e2e
```
