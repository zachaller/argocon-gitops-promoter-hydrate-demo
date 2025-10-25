# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 19cc71816f9a77d55464f31dac70419a7e1bb1fd
kustomize build ./user-configuration/staging/integration
```
