# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 69cb017fee52d16849a574fd5afa54793ed752f6
kustomize build ./user-configuration/staging/e2e
```
