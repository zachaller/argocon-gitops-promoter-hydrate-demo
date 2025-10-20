# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 33d44b66f86ed570f156c3e6c722e156452b2972
kustomize build ./user-configuration/development
```
