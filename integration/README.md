# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout eb458a3908af4b321b43c04f7fbe637be4582203
kustomize build ./user-configuration/staging/integration
```
