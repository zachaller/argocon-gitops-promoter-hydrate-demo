# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout b5c8b81153a17dfea50a2c075cf9d1be2e2b4263
kustomize build ./user-configuration/development
```
