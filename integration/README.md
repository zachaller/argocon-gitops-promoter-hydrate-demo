# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 2ca66c46a8e6d94ecfab5bd447d5988d6257fc88
kustomize build ./user-configuration/staging/integration
```
