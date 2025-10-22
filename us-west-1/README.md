# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout f13b387a5082157f93e32060131007d748aa3b77
kustomize build ./user-configuration/production/us-west-1
```
