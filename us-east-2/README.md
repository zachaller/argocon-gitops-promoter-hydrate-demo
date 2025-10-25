# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 379634e8cd4399f41a6e276d5393387fd646a146
kustomize build ./user-configuration/production/us-east-2
```
