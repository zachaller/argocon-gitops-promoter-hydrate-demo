# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 5a949de5dad46685ce3f6e95ee64e8cf39839fc7
kustomize build ./user-configuration/production/us-west-1
```
