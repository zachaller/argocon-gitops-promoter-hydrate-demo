# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 662c628a591beabe6ab792fb77b34d24af72aa02
kustomize build ./user-configuration/development
```
