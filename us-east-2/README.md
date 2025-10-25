# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 964a6ed073478fe1c804c5ee8d941bcab74e02d4
kustomize build ./user-configuration/production/us-east-2
```
