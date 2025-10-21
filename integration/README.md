# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 319f3599b14a175096864d07120ac76464d58100
kustomize build ./user-configuration/staging/integration
```
