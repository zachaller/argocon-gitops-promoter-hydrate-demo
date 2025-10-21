# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout b6ff1477dde2dc669e64571b6abe8d904bfe22e8
kustomize build ./user-configuration/development
```
