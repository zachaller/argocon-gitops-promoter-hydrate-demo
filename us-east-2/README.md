# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 370903cbcb44f08dd215aec1da8c03b3ecc4b221
kustomize build ./user-configuration/production/us-east-2
```
