# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 1372cd46b2da2df884ffc61e1a836a35f983fcd2
kustomize build ./user-configuration/development
```
