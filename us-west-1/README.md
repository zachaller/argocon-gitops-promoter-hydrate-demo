# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 71375f495e10c9bea8b3b12c714fe68500c98d7c
kustomize build ./user-configuration/production/us-west-1
```
