# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout a9d69baee49508113399b8b01ab0f54724c5158d
kustomize build ./user-configuration/development
```
