# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout a1e109369f1e42f8084060a749f656beb897d7e2
kustomize build ./user-configuration/production/us-east-2
```
