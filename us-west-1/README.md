# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout f751be8cab024d5f592d6e530c75bc5088693509
kustomize build ./user-configuration/production/us-west-1
```
