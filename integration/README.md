# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 3f96c21064d0e766e55c2866b7f49380b49dc047
kustomize build ./user-configuration/staging/integration
```
