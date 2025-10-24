# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout c03034facaf2f3d53d6ff9600e64c7f03257dc5e
kustomize build ./user-configuration/staging/integration
```
