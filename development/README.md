# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 4f110741dafe12095d3bc1372d4928dcdb3f6409
kustomize build ./user-configuration/development
```
