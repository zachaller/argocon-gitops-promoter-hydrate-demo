# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout d700573c6beef2524ec10a588e2fb0a991fccf19
kustomize build ./user-configuration/production/us-west-1
```
