# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout df0870fea0e413de84ec8f4a88d436d9dd1325b7
kustomize build ./user-configuration/production/us-east-2
```
