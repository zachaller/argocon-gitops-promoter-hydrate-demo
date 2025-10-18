# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 610fdb2bbfd974a8cb53e5591a8333eb5f0c7c7b
kustomize build ./user-configuration/production/us-east-2
```
