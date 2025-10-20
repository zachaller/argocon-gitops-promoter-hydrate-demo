# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout c6e6197c26dc7eeb8a9aa04ee0db9ddd9da754bd
kustomize build ./user-configuration/staging/integration
```
