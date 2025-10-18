# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 095708b0fab9fbc54df40e7b463ce0b83220516c
kustomize build ./user-configuration/production/us-west-1
```
