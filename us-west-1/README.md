# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 3b0400e56aa1863bdf33b8cf254a6834eee26173
kustomize build ./user-configuration/production/us-west-1
```
