# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 12f4e7e19d68d29b75b1688816c7b04367c745ba
kustomize build ./user-configuration/development
```
