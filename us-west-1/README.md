# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 5bb55a5457cce5f434ebc752728aab8694d06ee3
kustomize build ./user-configuration/production/us-west-1
```
