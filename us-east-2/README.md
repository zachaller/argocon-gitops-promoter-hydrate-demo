# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 7b9b13c5999baa29f8494c576b174eb129d70eff
kustomize build ./user-configuration/production/us-east-2
```
