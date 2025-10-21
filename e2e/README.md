# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout dfed87e4ff8d7be4f7c78c1f2fc01247d84c8ce4
kustomize build ./user-configuration/staging/e2e
```
