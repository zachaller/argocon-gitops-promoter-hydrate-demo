# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 1bcf86d1685428911d249cfd4a1181d471543653
kustomize build ./user-configuration/production/us-east-2
```
