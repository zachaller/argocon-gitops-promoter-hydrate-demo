# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout e1679fb0ca5137fe1976bf2e4de30b98e2f8fc0a
kustomize build ./user-configuration/staging/e2e
```
