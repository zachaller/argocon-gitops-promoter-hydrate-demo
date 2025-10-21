# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout b66d2a07a4e4348889f08ab92110f4234c1770a9
kustomize build ./user-configuration/production/us-west-1
```
