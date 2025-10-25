# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 0288e9ddd955852a3ead8aedb867a6e0622c1abc
kustomize build ./user-configuration/production/us-west-1
```
