# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout cd3fc345573300253f3f5c13bcd2cb36c6c3acf8
kustomize build ./user-configuration/production/us-east-2
```
