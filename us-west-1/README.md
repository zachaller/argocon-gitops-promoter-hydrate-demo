# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 0f0d08af6ca73ade3b94af1e11afb0203252284a
kustomize build ./user-configuration/production/us-west-1
```
