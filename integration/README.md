# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 5a38a4d41d56bf287b520bb8b3737bded7250778
kustomize build ./user-configuration/staging/integration
```
