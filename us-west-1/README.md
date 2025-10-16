# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout c538b6f7827a35c8d399a058e862d0e5447cb96c
kustomize build ./user-configuration/production/us-west-1
```
