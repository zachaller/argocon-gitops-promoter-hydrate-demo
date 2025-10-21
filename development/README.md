# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 44341d334b185c3f76bed899c4c49bbcf47042c4
kustomize build ./user-configuration/development
```
