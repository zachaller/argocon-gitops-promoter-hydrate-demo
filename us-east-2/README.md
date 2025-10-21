# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 9a8108de474c7e5000dd3ba067eeae64570bd6ec
kustomize build ./user-configuration/production/us-east-2
```
