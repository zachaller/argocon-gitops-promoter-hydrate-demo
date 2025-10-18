# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 7d0d1cf06e8a2978d7c865932a832169bab3a103
kustomize build ./user-configuration/development
```
