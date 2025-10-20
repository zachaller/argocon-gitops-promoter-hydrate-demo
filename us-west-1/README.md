# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout df2a64dae5630fd6774e48245e58d49543f878db
kustomize build ./user-configuration/production/us-west-1
```
