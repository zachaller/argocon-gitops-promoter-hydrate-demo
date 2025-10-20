# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout c236fc637f100165756164b0e97d24df6a7f8a19
kustomize build ./user-configuration/staging/integration
```
