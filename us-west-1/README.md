# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout d8d1f5a092bff4afe16ce2226bcecddd758ec9a1
kustomize build ./user-configuration/production/us-west-1
```
