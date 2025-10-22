# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout f51984743b6fd2b7254c1954099213df706d04c9
kustomize build ./user-configuration/production/us-west-1
```
