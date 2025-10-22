# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout e7e7ba7f81616daae3acb6be99598e86e16110b3
kustomize build ./user-configuration/production/us-east-2
```
