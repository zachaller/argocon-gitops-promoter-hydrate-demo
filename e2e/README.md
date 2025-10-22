# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout a68a362c056a81279327114a2d98239e397893a6
kustomize build ./user-configuration/staging/e2e
```
