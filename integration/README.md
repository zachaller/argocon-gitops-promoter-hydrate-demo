# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 2403ccaf861ab2de415cebf4348bcbbfe4f43b48
kustomize build ./user-configuration/staging/integration
```
