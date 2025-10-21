# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 24f53570546dd2afe6913a701f349c25587ed074
kustomize build ./user-configuration/staging/integration
```
