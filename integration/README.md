# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 3dbd748424f7e7008709b9b3cfc93f70ef0dac92
kustomize build ./user-configuration/staging/integration
```
