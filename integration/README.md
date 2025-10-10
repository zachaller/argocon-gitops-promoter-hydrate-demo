# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout a93b6dc70dab7c9076d35d2fbe8b2bc16d55408d
kustomize build ./user-configuration/staging/integration
```
