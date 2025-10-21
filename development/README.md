# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 351c70ac7b64610304418eea67ff438fd0c34d68
kustomize build ./user-configuration/development
```
