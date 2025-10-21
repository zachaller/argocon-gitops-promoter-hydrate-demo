# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 186cdcd7c16f0f48abfdcfc03dc9b09b3350e654
kustomize build ./user-configuration/staging/e2e
```
