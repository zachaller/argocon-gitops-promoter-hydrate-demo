# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 039bb802ddd5eab99f7971619217fa6649e88d45
kustomize build ./user-configuration/staging/e2e
```
