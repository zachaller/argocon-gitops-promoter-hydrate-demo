# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 8a58e7548b99094f078bc6784b25f91be56c7979
kustomize build ./user-configuration/staging/integration
```
