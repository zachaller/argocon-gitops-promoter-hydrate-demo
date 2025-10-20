# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 65332cb4090a04c4d7764c2f976bc87f67580722
kustomize build ./user-configuration/production/us-east-2
```
