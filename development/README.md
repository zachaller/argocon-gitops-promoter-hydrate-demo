# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 74cfb0bd91ec4ea327adffe192ec31690f86041f
kustomize build ./user-configuration/development
```
