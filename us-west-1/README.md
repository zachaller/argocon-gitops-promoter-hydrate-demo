# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout a13835deb10faf6f94b02b43fc9335fa40b35397
kustomize build ./user-configuration/production/us-west-1
```
