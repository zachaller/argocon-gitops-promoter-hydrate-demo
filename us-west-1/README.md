# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 9c1be1585171fb5e9a367552852b9654d4313602
kustomize build ./user-configuration/production/us-west-1
```
