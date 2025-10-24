# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout ad8342e595381ac8f10330f1c155778a732deabd
kustomize build ./user-configuration/staging/integration
```
