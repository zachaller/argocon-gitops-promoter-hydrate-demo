# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 211a7f85531b5990dec5c1652379cfd54321dc2b
kustomize build ./user-configuration/development
```
