# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout bcbdae62a7987875a9e15d6f4b62405d2e414f91
kustomize build ./user-configuration/staging/integration
```
