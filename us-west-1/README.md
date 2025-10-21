# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 3016db0d014887e32caa992bed9ba7db5a0d1fcf
kustomize build ./user-configuration/production/us-west-1
```
