# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 1b6bea1158ff16f9aa03f4fe436f25d53d7ff605
kustomize build ./user-configuration/staging/integration
```
