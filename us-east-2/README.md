# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 8d19a8192faaabc5cc537654f988db151dbba331
kustomize build ./user-configuration/production/us-east-2
```
