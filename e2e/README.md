# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 63b7a4d32d823084c24ceeb4bb0f63b03d7ed2ab
kustomize build ./user-configuration/staging/e2e
```
