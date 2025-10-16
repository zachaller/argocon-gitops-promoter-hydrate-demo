# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout cff0ed80d7402e879fb129c77468e1bb1fef74cb
kustomize build ./user-configuration/production/us-east-2
```
