# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout e19170b6441ca2975872dd7a856e5137917bfa1f
kustomize build ./user-configuration/staging/integration
```
