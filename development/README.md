# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 988943f250aadb4f2d54d0360af255e9bb0e00ab
kustomize build ./user-configuration/development
```
