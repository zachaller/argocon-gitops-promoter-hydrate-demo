# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 5e8c37966f12cc3066bb38ba197d36d8ad59431b
kustomize build ./user-configuration/staging/e2e
```
