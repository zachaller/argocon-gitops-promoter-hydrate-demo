# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 79108dccf8416909d3784f38b870d9bedf52013b
kustomize build ./user-configuration/production/us-west-1
```
