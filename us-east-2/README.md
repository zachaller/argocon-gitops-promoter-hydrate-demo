# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 58841333b6913d407cb4c5db0c809b92cef677b0
kustomize build ./user-configuration/production/us-east-2
```
