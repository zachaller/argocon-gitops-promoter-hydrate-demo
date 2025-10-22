# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 28caff62f66c749c9cb85062b3a28aae9f173180
kustomize build ./user-configuration/staging/integration
```
