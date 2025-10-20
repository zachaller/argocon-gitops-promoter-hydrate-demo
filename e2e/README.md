# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 7f03d179a958e21aebc387ba751df43258a7f560
kustomize build ./user-configuration/staging/e2e
```
