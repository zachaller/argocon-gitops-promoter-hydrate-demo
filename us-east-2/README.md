# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout a4e4ddf8d6f0ebd3c08abd963a7f8fe8ca482d2f
kustomize build ./user-configuration/production/us-east-2
```
