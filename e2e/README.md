# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout e404886f323be729b86d39716bf3de16f88e5ed0
kustomize build ./user-configuration/staging/e2e
```
