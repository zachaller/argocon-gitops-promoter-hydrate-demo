# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout feb2fe0a27ee5373a1dd48852cedc918a9a086e6
kustomize build ./user-configuration/development
```
