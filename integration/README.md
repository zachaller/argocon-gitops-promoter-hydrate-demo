# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 57fc79688fd1b492c6aec3ae11ba13140eb3682b
kustomize build ./user-configuration/staging/integration
```
