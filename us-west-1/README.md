# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 6a33cfc8415cf5079047eda7e56dc7244fea290a
kustomize build ./user-configuration/production/us-west-1
```
