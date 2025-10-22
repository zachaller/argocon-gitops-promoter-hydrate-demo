# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 6abd473ce0543f7653ac81007ad0424037260beb
kustomize build ./user-configuration/production/us-west-1
```
