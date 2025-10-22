# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 9a9c122fab8a8436707c8305978bee3d6c08a73c
kustomize build ./user-configuration/staging/e2e
```
