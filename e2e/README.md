# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 88d22d72594eb92481e93d9e47b491e43787eb44
kustomize build ./user-configuration/staging/e2e
```
