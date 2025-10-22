# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout e4bc27a379630d8e6f0af834bd5fd3c84a14b012
kustomize build ./user-configuration/development
```
