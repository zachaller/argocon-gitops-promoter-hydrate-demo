# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout ddf49be3bf3cf48231e2788fd657d700bb363387
kustomize build ./user-configuration/staging/integration
```
