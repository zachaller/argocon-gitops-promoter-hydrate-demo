# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout a10aacea09774620fd430cb69e065517f027d36d
kustomize build ./user-configuration/production/us-east-2
```
