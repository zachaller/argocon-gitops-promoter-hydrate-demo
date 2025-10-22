# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 9517e4f36be651cf304e05fe5d945317d5d9f3d8
kustomize build ./user-configuration/staging/e2e
```
