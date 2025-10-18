# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout b88cd049407dc878c56b425945942cd9a50cc567
kustomize build ./user-configuration/staging/integration
```
