# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 860a7de0996ea1b9ccd98a416928121f68fb1476
kustomize build ./user-configuration/development
```
