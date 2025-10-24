# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 1a30c33cd6f326a3045b954ba68144cd6cb04fc0
kustomize build ./user-configuration/production/us-west-1
```
