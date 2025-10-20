# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout cb60e1bc7d4bd70e63fd64238bf4bb161c8656ff
kustomize build ./user-configuration/staging/e2e
```
