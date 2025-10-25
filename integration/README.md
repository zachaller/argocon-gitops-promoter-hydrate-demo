# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 455611828137f20fbd7f963a8ddbc1aac1685788
kustomize build ./user-configuration/staging/integration
```
