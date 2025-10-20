# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout f2ea062f147dc6da25f8ccaf8ee385e0a6e37c70
kustomize build ./user-configuration/staging/integration
```
