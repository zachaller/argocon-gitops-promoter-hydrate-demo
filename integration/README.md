# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 3b95548f22a46d9830a5507af8eaec416ef34c3b
kustomize build ./user-configuration/staging/integration
```
