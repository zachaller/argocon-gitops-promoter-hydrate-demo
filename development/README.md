# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout f27e487ddabcea3f420e88c9228acbbcb7100e30
kustomize build ./user-configuration/development
```
