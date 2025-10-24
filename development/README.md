# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 9de1f1a6e7f823670d4df1226e6590b8f6b79e64
kustomize build ./user-configuration/development
```
