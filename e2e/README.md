# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 8dd8be793b39367f0d041aeefe621873f55d5f27
kustomize build ./user-configuration/staging/e2e
```
