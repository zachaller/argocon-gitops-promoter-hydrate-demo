# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 4873c1b609e6cafea56560867c70f1d6bef1224f
kustomize build ./user-configuration/development
```
