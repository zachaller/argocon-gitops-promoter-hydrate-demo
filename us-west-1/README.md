# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout ffbd16eaee663389460cfd4e57949237a464d9bb
kustomize build ./user-configuration/production/us-west-1
```
