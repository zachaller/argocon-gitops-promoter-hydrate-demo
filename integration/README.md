# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 714b36e8c0e046548b88295d7def22344d498020
kustomize build ./user-configuration/staging/integration
```
