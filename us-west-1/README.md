# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout daf86dc50b8d6d0546115684811d6e5a20eb9cb1
kustomize build ./user-configuration/production/us-west-1
```
