# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 4d05bd03508ddaa0bd70a798b98736acff0ac974
kustomize build ./user-configuration/production/us-west-1
```
