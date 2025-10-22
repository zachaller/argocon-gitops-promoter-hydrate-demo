# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout f0c44a47212d7ee8809c082d2ba7162ae1abc38d
kustomize build ./user-configuration/staging/integration
```
