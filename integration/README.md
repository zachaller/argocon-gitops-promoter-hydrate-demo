# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 6228e7d6092a1ea239f3728faa34ab1e22ceb377
kustomize build ./user-configuration/staging/integration
```
