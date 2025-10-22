# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 4a461c3d6f093f9e5bf535571ab4f64b18e1a7e8
kustomize build ./user-configuration/production/us-east-2
```
