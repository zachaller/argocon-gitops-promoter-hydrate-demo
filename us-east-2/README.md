# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 406b3dd14ac5b75e68e9e6b361969e68198ec4eb
kustomize build ./user-configuration/production/us-east-2
```
