# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout c4d80c0d6675c05cc2bd436bf54c382370ca16ae
kustomize build ./user-configuration/production/us-east-2
```
