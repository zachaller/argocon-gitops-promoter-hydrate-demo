# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout b3254ed9c871b6efb1a93998f5ce8f014461db08
kustomize build ./user-configuration/production/us-west-1
```
