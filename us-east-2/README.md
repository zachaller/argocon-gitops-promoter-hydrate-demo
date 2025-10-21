# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 3c173525c4ee6d216c0ceec5a04a98e645acaaa8
kustomize build ./user-configuration/production/us-east-2
```
