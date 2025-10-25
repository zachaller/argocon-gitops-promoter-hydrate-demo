# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout a2ab0527825b4ccc70e26b43942e6495314a37a4
kustomize build ./user-configuration/staging/integration
```
