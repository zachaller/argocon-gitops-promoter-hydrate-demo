# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 1cb89f4091b25cefbab40dd33206dd57c9b7442b
kustomize build ./user-configuration/development
```
