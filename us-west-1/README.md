# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout aae3b128cb68e6f9359bfce60e5fe15ab0cfff61
kustomize build ./user-configuration/production/us-west-1
```
