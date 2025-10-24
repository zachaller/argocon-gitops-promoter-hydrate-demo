# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 6bb817f93d1bfbe4b82fcccdee0b569cbad14023
kustomize build ./user-configuration/staging/integration
```
