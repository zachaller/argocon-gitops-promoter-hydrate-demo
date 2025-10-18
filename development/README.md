# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 367fd484e3ad71c687a8e93a9f76e0c7b13b5e9d
kustomize build ./user-configuration/development
```
