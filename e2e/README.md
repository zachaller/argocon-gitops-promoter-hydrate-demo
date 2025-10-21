# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 6a4fe4ac0beb874ca270ca12e33729388a75a825
kustomize build ./user-configuration/staging/e2e
```
