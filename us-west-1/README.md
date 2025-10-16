# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout a1c33e767f9899c259f51eb6c89866b3516c2484
kustomize build ./user-configuration/production/us-west-1
```
