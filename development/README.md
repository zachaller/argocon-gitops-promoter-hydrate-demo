# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout dbd5dad4bb8218741008d30d1d25a1b4d95c1fd8
kustomize build ./user-configuration/development
```
