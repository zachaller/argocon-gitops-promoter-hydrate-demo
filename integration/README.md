# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 98217ca81f9ecca05cb9f880b4b766dd05880c26
kustomize build ./user-configuration/staging/integration
```
