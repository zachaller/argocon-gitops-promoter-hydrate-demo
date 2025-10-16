# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 22bd2bf8ba835eb61b4de7f0bd6f3554825e2eb0
kustomize build ./user-configuration/production/us-west-1
```
