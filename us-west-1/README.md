# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout c4e947be4e5665f07c09e16eb54bd79e41357c63
kustomize build ./user-configuration/production/us-west-1
```
