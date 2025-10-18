# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 8be463f0dfe445929f72e5bae09bcf034e4ad6ab
kustomize build ./user-configuration/staging/integration
```
