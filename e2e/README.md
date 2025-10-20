# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 017532ea6151f403bb3f1441def722acd31cb63d
kustomize build ./user-configuration/staging/e2e
```
