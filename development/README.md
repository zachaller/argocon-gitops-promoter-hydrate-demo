# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout d0daa2540f0e39a0e2c47404e70382a2e82a4d72
kustomize build ./user-configuration/development
```
