# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout e3d291580c632613ed6bee142e812427cdb95d50
kustomize build ./user-configuration/production/us-west-1
```
