# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 8322c186b2f7525533f5323adb5eeb70d2e5c6f5
kustomize build ./user-configuration/staging/integration
```
