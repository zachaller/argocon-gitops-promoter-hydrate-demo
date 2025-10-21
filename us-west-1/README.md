# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 9594bfac6cabcab134ac70c1fcb24805a3ac85cb
kustomize build ./user-configuration/production/us-west-1
```
