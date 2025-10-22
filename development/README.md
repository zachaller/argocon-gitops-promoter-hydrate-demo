# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 9db7b7a6b6a4d3be74bcce7ebd0038ffc4d7cc5a
kustomize build ./user-configuration/development
```
