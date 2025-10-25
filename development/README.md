# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 4702bad519f9beea6d7c0b8bd46990041029662e
kustomize build ./user-configuration/development
```
