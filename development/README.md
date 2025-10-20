# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout e7a43f5b8137b864e0a62ccb2b7ee9d7e22f0d0a
kustomize build ./user-configuration/development
```
