# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout c4d4d7377fb1b410c6b7e9d22723f686720117d6
kustomize build ./user-configuration/production/us-west-1
```
