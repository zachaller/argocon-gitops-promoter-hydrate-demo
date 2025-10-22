# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 956179350031d82077479a585bb83b53ef84136e
kustomize build ./user-configuration/staging/integration
```
