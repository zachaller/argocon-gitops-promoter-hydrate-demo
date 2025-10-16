# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 63bff6cf8d565ac767a278159a468809a370c94d
kustomize build ./user-configuration/production/us-west-1
```
