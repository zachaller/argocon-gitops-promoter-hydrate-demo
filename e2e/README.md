# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 30b8ec493520b0951b5a261c685f6e40e9679772
kustomize build ./user-configuration/staging/e2e
```
