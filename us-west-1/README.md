# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 6d5054812904353693ba52a21d90febb485830ed
kustomize build ./user-configuration/production/us-west-1
```
