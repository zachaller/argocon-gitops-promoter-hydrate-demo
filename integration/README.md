# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout c8a6cf4fa7af98126904436e416e025d5085371b
kustomize build ./user-configuration/staging/integration
```
