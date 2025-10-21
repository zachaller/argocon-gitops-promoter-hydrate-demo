# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 49aa697d77a61cd3e2ae45798b41f893e457fc19
kustomize build ./user-configuration/staging/integration
```
