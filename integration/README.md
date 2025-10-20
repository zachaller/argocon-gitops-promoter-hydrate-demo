# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 00ad14a8ded3375ed2c8c4ba5e0a4cca163b7e15
kustomize build ./user-configuration/staging/integration
```
