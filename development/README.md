# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 2d26feeef5349dbec50b9314e32eca45b7776c70
kustomize build ./user-configuration/development
```
