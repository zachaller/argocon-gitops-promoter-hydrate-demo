# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout b28a69a420ad16e48cf55c9ee2837699c2d5c3fe
kustomize build ./user-configuration/production/us-east-2
```
