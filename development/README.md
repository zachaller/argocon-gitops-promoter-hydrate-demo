# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 9d98b3ea66abdb5fe1716b22e8e5d63dade7fa73
kustomize build ./user-configuration/development
```
