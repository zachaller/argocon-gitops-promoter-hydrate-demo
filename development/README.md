# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 04cfc6a1303adf7fbd62b9943a6516c42866cf81
kustomize build ./user-configuration/development
```
