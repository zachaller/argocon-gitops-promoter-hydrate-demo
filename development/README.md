# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 62f2784050c57927eb1abe16acf78ae4424ed531
kustomize build ./user-configuration/development
```
