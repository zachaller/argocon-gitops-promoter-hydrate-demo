# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 0eda5366e1ef8a342e04fe65f4a234fbec1d4f97
kustomize build ./user-configuration/staging/e2e
```
