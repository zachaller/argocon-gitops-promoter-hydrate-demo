# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 9227bc50b83ebe1f16db67a15d9d6e4d852bce0a
kustomize build ./user-configuration/staging/e2e
```
