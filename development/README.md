# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 55c17063a3733aaeb82068c29a5f3213aa482a7e
kustomize build ./user-configuration/development
```
