# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 48967ea26c0a5758246ea69e6c1adfa7d983e256
kustomize build ./user-configuration/staging/e2e
```
