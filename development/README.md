# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 00218705f84aca78e463d8d3104b5f465b1da183
kustomize build ./user-configuration/development
```
