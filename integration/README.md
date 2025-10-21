# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 63cad7c10ce1bcf52c28fb835b2f7149f9dc8b80
kustomize build ./user-configuration/staging/integration
```
