# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 9934ca0fb3c7cf664bcabe8c7f78ebc1b66a1dd1
kustomize build ./user-configuration/production/us-west-1
```
