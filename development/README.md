# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout d982ceac5d2a76f54ff77a874102cddbe5dc1180
kustomize build ./user-configuration/development
```
