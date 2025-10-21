# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout a06be951eab48a07125920e6cd349388733a6073
kustomize build ./user-configuration/production/us-east-2
```
