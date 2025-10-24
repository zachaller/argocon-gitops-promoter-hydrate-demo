# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 2b3493db7baa476e5f476f4b3e5d5fa7c3569092
kustomize build ./user-configuration/staging/integration
```
