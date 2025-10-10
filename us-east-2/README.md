# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 047feae67ede9978f9c7d25ed58a3a4398f4b073
kustomize build ./user-configuration/production/us-east-2
```
