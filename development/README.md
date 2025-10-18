# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 047bd0570d56e224c35fa667a442d912fd6c0bbe
kustomize build ./user-configuration/development
```
