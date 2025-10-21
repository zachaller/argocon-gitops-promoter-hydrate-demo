# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 17ad0f8e5f8d19f48c0dc66d6b7c185c18eed126
kustomize build ./user-configuration/development
```
