# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout f82fbfe60f92a03a0a660b80c1a4e850e282d4a9
kustomize build ./user-configuration/development
```
