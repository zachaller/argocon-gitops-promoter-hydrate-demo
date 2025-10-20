# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 4b63fa10dabc339988d5c6b2ca9745c13785a1fc
kustomize build ./user-configuration/production/us-west-1
```
