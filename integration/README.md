# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 633688da5b72670f9ae251f1fdfcc951ab02e901
kustomize build ./user-configuration/staging/integration
```
