# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 6b7a6b87789f1ca9f0207693f46b4e58e6707cdf
kustomize build ./user-configuration/production/us-west-1
```
