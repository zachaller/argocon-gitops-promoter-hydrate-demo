# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 963151b07489bc95356e8f5b59185027efad4a21
kustomize build ./user-configuration/staging/integration
```
