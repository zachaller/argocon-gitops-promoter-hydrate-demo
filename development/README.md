# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout e4a67e14744438c1b328f0e698ab1db1aea7bbdf
kustomize build ./user-configuration/development
```
