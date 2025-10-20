# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 774703b970c2d0e330473f7312221a2d8a577ee3
kustomize build ./user-configuration/production/us-east-2
```
