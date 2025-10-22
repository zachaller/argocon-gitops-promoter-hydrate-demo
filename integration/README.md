# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 9d7510bc6c770bbb8e544bd43d4f4e3131139dac
kustomize build ./user-configuration/staging/integration
```
