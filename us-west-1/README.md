# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 067b8b5210991e63c68f6d9384b283c04b6ee501
kustomize build ./user-configuration/production/us-west-1
```
