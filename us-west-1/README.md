# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 4ed4240fc283d7b96007d17f6632cfc34bd0a55a
kustomize build ./user-configuration/production/us-west-1
```
