# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 9b741cb9cd03060fa16f953c49ad46bdda06886b
kustomize build ./user-configuration/staging/integration
```
