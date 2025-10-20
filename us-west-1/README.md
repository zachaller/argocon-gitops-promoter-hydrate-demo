# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout f05f88180318584dea7417728e6fd2103cf13a24
kustomize build ./user-configuration/production/us-west-1
```
